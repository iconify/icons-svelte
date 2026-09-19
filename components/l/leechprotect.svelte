<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntk51_c5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="ntk51_c5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:leechprotect" {...props}></Icon>
