<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loz5rn4-x.css';
import '../../css/m/m9ropn74r.css';
import '../../css/z/zmcrrdb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="loz5rn4-x"/><path class="m9ropn74r"/><path class="zmcrrdb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chevrons-up-down" {...props}></Icon>
