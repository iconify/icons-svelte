<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6nw9ybaa.css';
import '../../css/n/n3vra2bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6nw9ybaa"/><path class="n3vra2bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:article" {...props}></Icon>
