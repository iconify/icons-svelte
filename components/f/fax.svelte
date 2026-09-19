<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8a9ik84v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="u8a9ik84v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:fax" {...props}></Icon>
