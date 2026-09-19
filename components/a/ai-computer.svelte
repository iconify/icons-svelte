<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qa9f7xbjt.css';
import '../../css/o/oiu-3i4pj.css';
import '../../css/s/s5n1v6bqp.css';
import '../../css/e/excc-72qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qa9f7xbjt"/><path class="oiu-3i4pj"/><path class="s5n1v6bqp"/><path class="excc-72qq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-computer" {...props}></Icon>
