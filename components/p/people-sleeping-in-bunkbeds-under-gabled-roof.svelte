<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab7d9sbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ab7d9sbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:people-sleeping-in-bunkbeds-under-gabled-roof" {...props}></Icon>
