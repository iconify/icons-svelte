<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1x6-acbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="o1x6-acbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:hourglass6" {...props}></Icon>
