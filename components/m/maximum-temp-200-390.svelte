<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvwx6cb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":472};
const content = `<path class="bvwx6cb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:maximum-temp-200-390" {...props}></Icon>
