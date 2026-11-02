<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my4upjy5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="my4upjy5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sleeping-in-shelter" {...props}></Icon>
