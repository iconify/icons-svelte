<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8hrerbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="u8hrerbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:p-upper-case" {...props}></Icon>
