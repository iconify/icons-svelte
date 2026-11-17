<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4wa7qbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h4wa7qbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mytview-dark" {...props}></Icon>
