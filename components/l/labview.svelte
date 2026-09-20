<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdck0tbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdck0tbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:labview" {...props}></Icon>
