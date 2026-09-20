<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2wv6_umn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z2wv6_umn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:admin" {...props}></Icon>
