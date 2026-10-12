<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn_uf6bnc.css';
import '../../css/i/ivhxmubfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bn_uf6bnc"/><path class="ivhxmubfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-check-fill-20" {...props}></Icon>
