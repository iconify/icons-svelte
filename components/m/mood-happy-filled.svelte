<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spegpt8ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spegpt8ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-happy-filled" {...props}></Icon>
