<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzjt250kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzjt250kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-dollar-fill-round" {...props}></Icon>
