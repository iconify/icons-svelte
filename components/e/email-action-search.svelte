<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/ivr6k85sh.css';
import '../../css/t/txzeh5b2m.css';
import '../../css/g/gw2b5ibjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ivr6k85sh"/><path class="txzeh5b2m"/><path class="gw2b5ibjm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:email-action-search" {...props}></Icon>
