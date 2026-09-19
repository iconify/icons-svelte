<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyf3bcc0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lyf3bcc0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-merge" {...props}></Icon>
