<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4gy22yti.css';
import '../../css/i/ifweg2bug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e4gy22yti"/><path class="ifweg2bug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ground-loop-48" {...props}></Icon>
