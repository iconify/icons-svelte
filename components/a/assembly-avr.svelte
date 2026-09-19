<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4yqpq1og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y4yqpq1og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:assembly-avr" {...props}></Icon>
