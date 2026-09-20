<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5jew8byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o5jew8byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bar-15" {...props}></Icon>
