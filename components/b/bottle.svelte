<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi3edprxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yi3edprxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bottle" {...props}></Icon>
