<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grcw_sb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grcw_sb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:polywork" {...props}></Icon>
