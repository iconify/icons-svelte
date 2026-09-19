<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwkghnbhw.css';
import '../../css/g/guuurn7sm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nwkghnbhw"/><path class="guuurn7sm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:download-fill-16" {...props}></Icon>
