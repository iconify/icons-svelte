<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if3jwc7or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="if3jwc7or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:bashly-hook" {...props}></Icon>
