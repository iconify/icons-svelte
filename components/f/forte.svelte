<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p17ncey3b.css';
import '../../css/s/s5j8cpt3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p17ncey3b"/><path class="s5j8cpt3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:forte" {...props}></Icon>
