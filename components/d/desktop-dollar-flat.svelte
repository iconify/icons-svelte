<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bqiva3mde.css';
import '../../css/l/lg601bbea.css';
import '../../css/y/yt4_aebpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bqiva3mde"/><path class="lg601bbea"/><path class="yt4_aebpl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:desktop-dollar-flat" {...props}></Icon>
