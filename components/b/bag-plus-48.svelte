<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb2gho-_w.css';
import '../../css/e/e6f488wbx.css';
import '../../css/c/c4_zttl1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cb2gho-_w"/><path class="e6f488wbx"/><path class="c4_zttl1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bag-plus-48" {...props}></Icon>
