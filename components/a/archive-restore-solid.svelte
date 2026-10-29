<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jteh5fb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jteh5fb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:archive-restore-solid" {...props}></Icon>
