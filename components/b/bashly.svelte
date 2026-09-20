<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss_f9kbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ss_f9kbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:bashly" {...props}></Icon>
