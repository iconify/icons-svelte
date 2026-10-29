<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg00i_boh.css';
import '../../css/h/h1a9fqbsg.css';
import '../../css/d/d91l8hv0w.css';
import '../../css/s/slojpgbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg00i_boh wm-k"/><path class="h1a9fqbsg wm-k"/><path class="d91l8hv0w wm-s"/><path class="slojpgbec wm-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:mail-check" {...props}></Icon>
