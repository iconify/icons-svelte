<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sasdp3y_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sasdp3y_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:badge-check-gloss" {...props}></Icon>
