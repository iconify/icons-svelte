<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkx37hb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkx37hb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-type-corner-sharp" {...props}></Icon>
