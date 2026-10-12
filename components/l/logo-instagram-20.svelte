<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7pypebcb.css';
import '../../css/c/cgjl_2bdu.css';
import '../../css/m/m2-yovtjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r7pypebcb"/><path class="cgjl_2bdu"/><path class="m2-yovtjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:logo-instagram-20" {...props}></Icon>
