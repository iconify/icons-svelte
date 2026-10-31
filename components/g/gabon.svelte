<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgu_qf8mr.css';
import '../../css/n/nirbr8brm.css';
import '../../css/a/aot_jkqqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="fgu_qf8mr"/><path class="nirbr8brm"/><path class="aot_jkqqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:gabon" {...props}></Icon>
