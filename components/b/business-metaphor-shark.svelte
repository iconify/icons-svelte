<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fjiiugs0p.css';
import '../../css/t/t1whsxqdu.css';
import '../../css/w/wgfaujbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fjiiugs0p"/><path class="t1whsxqdu"/><path class="wgfaujbey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:business-metaphor-shark" {...props}></Icon>
