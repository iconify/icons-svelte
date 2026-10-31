<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si4c_jo9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si4c_jo9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heading-gloss" {...props}></Icon>
