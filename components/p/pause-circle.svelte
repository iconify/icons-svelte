<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhlzq_blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hhlzq_blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:pause-circle" {...props}></Icon>
