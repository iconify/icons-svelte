<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlch2l75t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qlch2l75t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-sharepoint-dark" {...props}></Icon>
