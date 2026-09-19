<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg8l3b1wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg8l3b1wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:golf" {...props}></Icon>
