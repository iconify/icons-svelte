<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_cf4dbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_cf4dbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:google-photos" {...props}></Icon>
