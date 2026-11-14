<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcrvamb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fcrvamb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dokuwiki-light" {...props}></Icon>
