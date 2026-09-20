<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9dhk5b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9dhk5b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-b-filled" {...props}></Icon>
