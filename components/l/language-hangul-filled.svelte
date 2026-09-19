<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s08092quh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s08092quh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-hangul-filled" {...props}></Icon>
