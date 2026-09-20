<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3c3p4byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3c3p4byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar" {...props}></Icon>
