<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dskmdxbel.css';
import '../../css/z/z0k1ug9bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dskmdxbel"/><path class="z0k1ug9bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cabinet" {...props}></Icon>
