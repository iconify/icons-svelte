<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddtzh172g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ddtzh172g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hanko" {...props}></Icon>
