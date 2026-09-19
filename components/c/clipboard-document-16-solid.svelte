<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymn_uab8u.css';
import '../../css/x/xpn17_exa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ymn_uab8u"/><path class="xpn17_exa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:clipboard-document-16-solid" {...props}></Icon>
