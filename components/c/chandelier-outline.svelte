<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh6h5ybii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zh6h5ybii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chandelier-outline" {...props}></Icon>
