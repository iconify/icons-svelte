<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etjoxb8eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etjoxb8eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:library-books" {...props}></Icon>
