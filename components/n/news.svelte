<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p13ni4b9t.css';
import '../../css/n/n3vra2bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p13ni4b9t"/><path class="n3vra2bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:news" {...props}></Icon>
