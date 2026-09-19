<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brgyq0v3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="brgyq0v3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:moon" {...props}></Icon>
