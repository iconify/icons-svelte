<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohhtp_cah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohhtp_cah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dotted-letter-d" {...props}></Icon>
