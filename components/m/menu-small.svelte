<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6v6--uhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="t6v6--uhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:menu-small" {...props}></Icon>
