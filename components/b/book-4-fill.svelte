<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii1xarbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii1xarbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-4-fill" {...props}></Icon>
