<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg6t5bctu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":430,"height":512};
const content = `<path class="eg6t5bctu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:grunt" {...props}></Icon>
