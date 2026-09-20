<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl8ppyb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl8ppyb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:redux" {...props}></Icon>
