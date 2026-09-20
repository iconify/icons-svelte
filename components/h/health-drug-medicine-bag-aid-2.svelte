<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfzl3xbxr.css';
import '../../css/h/hte0qdbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nfzl3xbxr"/><path class="hte0qdbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-drug-medicine-bag-aid-2" {...props}></Icon>
