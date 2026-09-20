<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le4ktn-ax.css';
import '../../css/q/qfz352b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="le4ktn-ax"/><path class="qfz352b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-stopwatch" {...props}></Icon>
