<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urtl6lb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="urtl6lb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:emailexport" {...props}></Icon>
