<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nspkqstcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nspkqstcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chevron-left" {...props}></Icon>
