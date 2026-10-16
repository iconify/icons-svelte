<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8spygx2w.css';
import '../../css/f/fkn2szbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a8spygx2w"/><path class="fkn2szbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rack-and-pinion-48-bold" {...props}></Icon>
