<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7wz_k0tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7wz_k0tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:eye-closed" {...props}></Icon>
