<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppv_c6bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ppv_c6bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:building-lock" {...props}></Icon>
