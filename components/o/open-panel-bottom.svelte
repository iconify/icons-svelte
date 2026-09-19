<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nft3n5nlm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nft3n5nlm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:open-panel-bottom" {...props}></Icon>
