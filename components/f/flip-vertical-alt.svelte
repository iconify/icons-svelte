<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5_l9__yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h5_l9__yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:flip-vertical-alt" {...props}></Icon>
