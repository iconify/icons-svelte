<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qmyruqboo.css';
import '../../css/i/iqvxyvbht.css';
import '../../css/x/xfrwc6b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qmyruqboo"/><path class="iqvxyvbht"/><path class="xfrwc6b-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:microprocessor-computer-chip-overheat" {...props}></Icon>
