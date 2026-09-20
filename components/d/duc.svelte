<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwg2hccwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kwg2hccwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:duc" {...props}></Icon>
