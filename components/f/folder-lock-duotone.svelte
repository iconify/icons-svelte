<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g8qdoms0h.css';
import '../../css/l/lmmrxwb9j.css';
import '../../css/e/e1hj2ybxs.css';
import '../../css/k/kewqfdbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g8qdoms0h"/><path class="lmmrxwb9j"/><path class="e1hj2ybxs"/><path class="kewqfdbji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-lock-duotone" {...props}></Icon>
