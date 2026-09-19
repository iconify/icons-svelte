<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_ic-2bov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d_ic-2bov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:arch" {...props}></Icon>
