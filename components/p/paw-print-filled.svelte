<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obo_3dbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obo_3dbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:paw-print-filled" {...props}></Icon>
