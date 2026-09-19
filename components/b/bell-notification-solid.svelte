<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqa3tkb1n.css';
import '../../css/y/y1ufbo1la.css';
import '../../css/x/xe0pjblnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="sqa3tkb1n"><path class="y1ufbo1la"/><path class="xe0pjblnt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:bell-notification-solid" {...props}></Icon>
