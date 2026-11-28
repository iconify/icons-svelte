<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2ztp6gpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="s2ztp6gpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:replay-10-bold" {...props}></Icon>
