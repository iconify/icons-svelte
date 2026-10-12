<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zhcedhb7f.css';
import '../../css/k/knbgc0bhr.css';
import '../../css/k/ksm8fhndt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zhcedhb7f"/><path class="knbgc0bhr"/><path class="ksm8fhndt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bed-duotone" {...props}></Icon>
