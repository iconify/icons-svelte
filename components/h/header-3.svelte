<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoc34syxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-6.5};
const content = `<path class="xoc34syxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:header-3" {...props}></Icon>
