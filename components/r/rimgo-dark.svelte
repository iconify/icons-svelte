<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z15mw-brh.css';
import '../../css/j/jdcotzpev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z15mw-brh"/><circle class="jdcotzpev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rimgo-dark" {...props}></Icon>
