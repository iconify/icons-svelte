<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edzw4y5pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="edzw4y5pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:football" {...props}></Icon>
