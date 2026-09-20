<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sseqasvtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sseqasvtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:atom" {...props}></Icon>
