<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w-_7j2b_b.css';
import '../../css/t/tghze73ng.css';
import '../../css/u/u26uafbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="w-_7j2b_b"/><path class="tghze73ng"/><path class="u26uafbbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:monetization-mouse" {...props}></Icon>
