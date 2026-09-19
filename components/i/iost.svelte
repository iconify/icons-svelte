<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlp09obxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rlp09obxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:iost" {...props}></Icon>
