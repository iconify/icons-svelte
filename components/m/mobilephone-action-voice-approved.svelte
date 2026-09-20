<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rpjys_o5s.css';
import '../../css/u/u0vw5sb0i.css';
import '../../css/w/we7ulucfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rpjys_o5s"/><path class="u0vw5sb0i"/><path class="we7ulucfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:mobilephone-action-voice-approved" {...props}></Icon>
