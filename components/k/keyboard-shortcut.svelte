<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxqvxtb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yxqvxtb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:keyboard-shortcut" {...props}></Icon>
