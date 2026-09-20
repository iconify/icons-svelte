<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2y0d8bfl.css';
import '../../css/e/exps9_t7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2y0d8bfl"/><path class="exps9_t7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hail-line" {...props}></Icon>
