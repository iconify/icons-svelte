<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-mrcre1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-mrcre1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:catalog-1" {...props}></Icon>
