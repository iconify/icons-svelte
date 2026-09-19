<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgz295blo.css';
import '../../css/g/g_z5fgbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgz295blo"/><path class="g_z5fgbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-right-square-half" {...props}></Icon>
