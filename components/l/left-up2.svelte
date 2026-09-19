<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scu44gudw.css';
import '../../css/z/zfka66bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="scu44gudw"/><path class="zfka66bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:left-up2" {...props}></Icon>
