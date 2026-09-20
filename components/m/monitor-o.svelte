<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfz7s0qpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yfz7s0qpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:monitor-o" {...props}></Icon>
