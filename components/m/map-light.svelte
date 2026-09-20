<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t98jbcwdn.css';
import '../../css/m/msqpicc3e.css';
import '../../css/b/bkyqy-baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t98jbcwdn"/><path class="msqpicc3e"/><circle class="bkyqy-baq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:map-light" {...props}></Icon>
