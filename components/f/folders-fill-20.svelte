<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj96y1j8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lj96y1j8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:folders-fill-20" {...props}></Icon>
