<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kuisey8iv.css';
import '../../css/v/vkprnmhcj.css';
import '../../css/m/mi0sarbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kuisey8iv"/><path class="vkprnmhcj"/><path class="mi0sarbdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:apron" {...props}></Icon>
