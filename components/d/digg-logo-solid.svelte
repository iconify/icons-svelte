<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyzrjtbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kyzrjtbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:digg-logo-solid" {...props}></Icon>
