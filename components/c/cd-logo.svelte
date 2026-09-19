<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti_mu752a.css';
import '../../css/o/ocqrknbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ti_mu752a"/><path class="ocqrknbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:cd-logo" {...props}></Icon>
