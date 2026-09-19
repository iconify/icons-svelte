<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue4v1ubkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue4v1ubkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:lock" {...props}></Icon>
