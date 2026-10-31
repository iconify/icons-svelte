<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/x/x6falv9am.css';
import '../../css/h/hjr5enbkw.css';
import '../../css/n/nly9vkofp.css';
import '../../css/w/wkbf8vbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow x6falv9am"/><path class="hjr5enbkw wm-shadow"/><path class="nly9vkofp"/><path class="wkbf8vbre"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:cloud-lightning" {...props}></Icon>
