<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jj_5alors.css';
import '../../css/x/x7r6vrb4q.css';
import '../../css/c/cl4qfyg_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jj_5alors"/><path class="x7r6vrb4q"/><path class="cl4qfyg_q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mails-duotone" {...props}></Icon>
