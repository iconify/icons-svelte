<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh2ythp9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh2ythp9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-project-tia-filled" {...props}></Icon>
