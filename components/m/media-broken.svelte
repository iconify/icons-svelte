<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv6beyi_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fv6beyi_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:media-broken" {...props}></Icon>
