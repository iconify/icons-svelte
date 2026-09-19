<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1eef546k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a1eef546k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:right-black-triangle-filled" {...props}></Icon>
