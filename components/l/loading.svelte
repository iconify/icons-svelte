<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-y8v8h3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f-y8v8h3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:loading" {...props}></Icon>
