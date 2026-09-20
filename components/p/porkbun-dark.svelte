<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d99rwehuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d99rwehuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:porkbun-dark" {...props}></Icon>
