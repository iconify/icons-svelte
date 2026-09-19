<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl8n7bazd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sl8n7bazd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cartalt" {...props}></Icon>
