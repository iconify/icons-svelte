<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv-ekvb3r.css';
import '../../css/y/yze3d2bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv-ekvb3r"/><path class="yze3d2bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:finger-swipe-up-filled" {...props}></Icon>
