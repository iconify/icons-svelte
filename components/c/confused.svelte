<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gshe_di8n.css';
import '../../css/w/ww076bcwj.css';
import '../../css/n/ngo67db0o.css';
import '../../css/d/dy-ttul4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gshe_di8n"/><path class="ww076bcwj"/><path class="ngo67db0o"/><path class="dy-ttul4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:confused" {...props}></Icon>
