<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-cm0ty8h.css';
import '../../css/u/uwwux4bdl.css';
import '../../css/l/l_fae7rzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i-cm0ty8h"/><path class="uwwux4bdl"/><path class="l_fae7rzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-database-filled" {...props}></Icon>
