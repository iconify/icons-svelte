<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-3f8hxqz.css';
import '../../css/c/cdssnbbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-3f8hxqz"/><path class="cdssnbbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bank" {...props}></Icon>
