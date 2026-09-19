<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic4y8cbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="ic4y8cbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:meanpath" {...props}></Icon>
