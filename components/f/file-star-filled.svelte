<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdv2q9x8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdv2q9x8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-star-filled" {...props}></Icon>
