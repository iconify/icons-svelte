<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbwwa7bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":422,"height":512};
const content = `<path class="sbwwa7bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:babel" {...props}></Icon>
