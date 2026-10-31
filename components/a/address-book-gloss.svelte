<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp3np7bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp3np7bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:address-book-gloss" {...props}></Icon>
