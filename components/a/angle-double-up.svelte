<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a33b94myo.css';
import '../../css/o/o08jojm8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a33b94myo"/><path class="o08jojm8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:angle-double-up" {...props}></Icon>
