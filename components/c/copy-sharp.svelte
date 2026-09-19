<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhwkk-pks.css';
import '../../css/s/spak13bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jhwkk-pks"/><path class="spak13bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:copy-sharp" {...props}></Icon>
