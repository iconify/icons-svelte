<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw5mp2kwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="zw5mp2kwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:line" {...props}></Icon>
