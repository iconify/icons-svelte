<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xzi62pqbj.css';
import '../../css/h/hmocrmbht.css';
import '../../css/a/am_q_ho_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xzi62pqbj"/><path class="hmocrmbht"/><path class="am_q_ho_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:money-coin-stack" {...props}></Icon>
