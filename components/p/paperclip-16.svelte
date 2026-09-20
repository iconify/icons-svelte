<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh4fvekho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kh4fvekho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:paperclip-16" {...props}></Icon>
