<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyv4pt_zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyv4pt_zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clear-octagon-outline" {...props}></Icon>
