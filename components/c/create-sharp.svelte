<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjpro_u9e.css';
import '../../css/q/q0wqs_b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xjpro_u9e"/><path class="q0wqs_b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:create-sharp" {...props}></Icon>
