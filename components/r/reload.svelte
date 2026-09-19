<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g44z7fuun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g44z7fuun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:reload" {...props}></Icon>
