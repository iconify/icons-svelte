<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zftneacjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zftneacjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:alibaba-cloud-fill" {...props}></Icon>
