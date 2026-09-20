<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s27ky2-ij.css';
import '../../css/i/i2crm77yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s27ky2-ij"/><path class="i2crm77yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-macos-open" {...props}></Icon>
