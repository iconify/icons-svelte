<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iel2hrbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iel2hrbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:playcircle" {...props}></Icon>
