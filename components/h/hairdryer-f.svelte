<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khk5qrb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="khk5qrb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:hairdryer-f" {...props}></Icon>
