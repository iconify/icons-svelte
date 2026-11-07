<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w482_wbjc.css';
import '../../css/a/a0-ehlbuo.css';
import '../../css/z/zs0elrbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w482_wbjc"/><path class="a0-ehlbuo"/><path class="zs0elrbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:layout-freeform-bold" {...props}></Icon>
