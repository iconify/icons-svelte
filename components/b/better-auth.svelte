<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1s_e0b7s.css';
import '../../css/c/cvuri1beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1s_e0b7s"/><path class="cvuri1beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:better-auth" {...props}></Icon>
