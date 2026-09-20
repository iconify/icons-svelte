<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygvme9b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygvme9b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:renren-logo-2" {...props}></Icon>
