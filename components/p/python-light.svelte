<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abbyiwbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="abbyiwbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:python-light" {...props}></Icon>
