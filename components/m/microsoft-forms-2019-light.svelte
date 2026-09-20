<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_ttfbbvt.css';
import '../../css/j/j29g_4b6w.css';
import '../../css/n/nzpzadcnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y_ttfbbvt"/><path class="j29g_4b6w"/><path class="nzpzadcnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-forms-2019-light" {...props}></Icon>
