<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7g9menyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="o7g9menyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face3-small-filled" {...props}></Icon>
