<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqbx70bbt.css';
import '../../css/w/wvdczzbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nqbx70bbt"/><path class="wvdczzbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:picnic-48" {...props}></Icon>
