<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbk9oiw8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbk9oiw8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:document-report" {...props}></Icon>
