<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khb128k1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="khb128k1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:backpack" {...props}></Icon>
