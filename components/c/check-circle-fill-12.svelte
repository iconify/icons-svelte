<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2_9i5x-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="o2_9i5x-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:check-circle-fill-12" {...props}></Icon>
