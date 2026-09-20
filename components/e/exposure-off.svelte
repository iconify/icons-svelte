<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa3qufpne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wa3qufpne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:exposure-off" {...props}></Icon>
