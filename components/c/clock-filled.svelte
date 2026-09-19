<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1_6q1b6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z1_6q1b6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:clock-filled" {...props}></Icon>
