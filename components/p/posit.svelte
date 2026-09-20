<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxq3-nspf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxq3-nspf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:posit" {...props}></Icon>
