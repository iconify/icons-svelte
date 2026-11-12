<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb67ukblf.css';
import '../../css/i/iclst2bgx.css';
import '../../css/d/dtug5xo5w.css';
import '../../css/v/vkhq0_bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cb67ukblf"/><path class="iclst2bgx"/><path class="dtug5xo5w"/><path class="vkhq0_bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-kmeet" {...props}></Icon>
