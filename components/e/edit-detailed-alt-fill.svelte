<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2j_xrb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2j_xrb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:edit-detailed-alt-fill" {...props}></Icon>
