<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e74j4sj4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e74j4sj4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:analytics" {...props}></Icon>
