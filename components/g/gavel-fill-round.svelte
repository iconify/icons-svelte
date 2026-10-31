<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt0k6kbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt0k6kbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:gavel-fill-round" {...props}></Icon>
