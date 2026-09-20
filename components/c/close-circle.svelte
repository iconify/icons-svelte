<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/m/maq17k.css';
import '../../css/b/bxgp8e.css';
import '../../css/s/so-from-60.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c maq17k"/><path class="a0m25c bxgp8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:close-circle" {...props}></Icon>
