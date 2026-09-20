<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5_s4_b4r.css';
import '../../css/i/iukkl9xoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5_s4_b4r"/><path class="iukkl9xoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:10set" {...props}></Icon>
