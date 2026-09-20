<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyyypq67t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kyyypq67t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:peppermint-light" {...props}></Icon>
