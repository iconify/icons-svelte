<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfnt_40zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfnt_40zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-alert" {...props}></Icon>
