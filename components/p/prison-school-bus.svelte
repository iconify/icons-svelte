<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv8thob0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="yv8thob0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:prison-school-bus" {...props}></Icon>
