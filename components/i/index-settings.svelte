<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo6jjhb5p.css';
import '../../css/e/eroa1ibmd.css';
import '../../css/e/ebh6vui7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lo6jjhb5p"/><path class="eroa1ibmd"/><path class="ebh6vui7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:index-settings" {...props}></Icon>
