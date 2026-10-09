<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8im5qk_h.css';
import '../../css/z/zg81-pbvk.css';
import '../../css/n/nga2r_t3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w8im5qk_h"/><path class="zg81-pbvk"/><path class="nga2r_t3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-plus-20-bold" {...props}></Icon>
