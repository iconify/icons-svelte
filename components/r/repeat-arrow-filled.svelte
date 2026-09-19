<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n22-7p18b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="n22-7p18b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:repeat-arrow-filled" {...props}></Icon>
