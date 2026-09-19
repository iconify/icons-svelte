<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s00qr5bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s00qr5bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:hide" {...props}></Icon>
