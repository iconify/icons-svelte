<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_fv_k1pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_fv_k1pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:life-hacking" {...props}></Icon>
