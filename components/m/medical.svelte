<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cft_k0b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="cft_k0b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:medical" {...props}></Icon>
