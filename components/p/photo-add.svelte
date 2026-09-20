<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q5cqyabqx.css';
import '../../css/u/uuwchf_9c.css';
import '../../css/k/kgqskh4kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="q5cqyabqx"/><path class="uuwchf_9c"/><path clip-rule="evenodd" class="kgqskh4kt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:photo-add" {...props}></Icon>
