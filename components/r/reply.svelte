<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4412r2nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i4412r2nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:reply" {...props}></Icon>
