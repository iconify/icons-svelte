<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2_wgcb5j.css';
import '../../css/h/h1kxnnbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2_wgcb5j duoicon-secondary-layer"/><path class="duoicon-primary-layer h1kxnnbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:book" {...props}></Icon>
