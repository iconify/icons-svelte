<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdjq2-vym.css';
import '../../css/x/xgndkg1rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdjq2-vym"/><path class="xgndkg1rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:blank-alt-duotone" {...props}></Icon>
