<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7phojbjv.css';
import '../../css/o/ojlbdmb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7phojbjv"/><path class="ojlbdmb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-bookmarks" {...props}></Icon>
