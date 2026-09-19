<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egkgr_f8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="egkgr_f8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:makerbot" {...props}></Icon>
