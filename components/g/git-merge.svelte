<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te_k_zb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="te_k_zb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:git-merge" {...props}></Icon>
