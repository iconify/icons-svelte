<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr37rf74y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr37rf74y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bag-checked" {...props}></Icon>
