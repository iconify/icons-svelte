<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqur01bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":551,"height":634};
const content = `<path class="fqur01bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:dark" {...props}></Icon>
