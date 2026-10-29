<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxj_cdcom.css';
import '../../css/h/h1a9fqbsg.css';
import '../../css/o/ozm2d0b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxj_cdcom wm-k"/><path class="h1a9fqbsg wm-k"/><path class="ozm2d0b9u wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:mail" {...props}></Icon>
