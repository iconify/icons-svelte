<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptgr-wbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ptgr-wbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:gold-solid" {...props}></Icon>
