<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skm696e6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="skm696e6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:book" {...props}></Icon>
