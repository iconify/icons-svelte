<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k0bqss54y.css';
import '../../css/k/khng8rbjh.css';
import '../../css/q/qjxwpdimh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k0bqss54y"/><path class="khng8rbjh"/><path class="qjxwpdimh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:dessert-duotone" {...props}></Icon>
