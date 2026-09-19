<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkve5bctc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkve5bctc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-dashboard" {...props}></Icon>
