<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_7p9s-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":771,"height":1024};
const content = `<path class="nz_7p9s-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:kohana" {...props}></Icon>
