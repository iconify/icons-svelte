<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd4yhsbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd4yhsbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:deviant-art-logo-2-solid" {...props}></Icon>
