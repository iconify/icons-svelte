<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/horse9bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="horse9bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:book-filled" {...props}></Icon>
