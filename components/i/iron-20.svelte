<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liufp_b5i.css';
import '../../css/m/mgw7p7bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="liufp_b5i"/><path class="mgw7p7bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:iron-20" {...props}></Icon>
