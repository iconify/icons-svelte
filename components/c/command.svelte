<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iof1jrb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="iof1jrb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:command" {...props}></Icon>
