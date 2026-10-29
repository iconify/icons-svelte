<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hya0m4b1r.css';
import '../../css/u/utm1ftb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hya0m4b1r wm-k"/><path class="utm1ftb-c wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:candy-cane" {...props}></Icon>
