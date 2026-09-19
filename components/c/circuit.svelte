<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkxahjftn.css';
import '../../css/x/xxi34xgyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hkxahjftn"/><path class="xxi34xgyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:circuit" {...props}></Icon>
