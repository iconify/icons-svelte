<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-bnk7bok.css';
import '../../css/j/jzfn62btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="f-bnk7bok"/><path class="jzfn62btm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:monitor-stop-duotone" {...props}></Icon>
