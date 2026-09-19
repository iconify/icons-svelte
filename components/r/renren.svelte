<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6u5cc1jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="i6u5cc1jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:renren" {...props}></Icon>
