<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5dtybw4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":704};
const content = `<path class="g5dtybw4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:behance" {...props}></Icon>
