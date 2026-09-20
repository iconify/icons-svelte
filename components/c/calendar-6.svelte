<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7qvz7mub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h7qvz7mub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:calendar-6" {...props}></Icon>
