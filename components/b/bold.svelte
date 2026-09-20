<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhc4o5kia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="yhc4o5kia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:bold" {...props}></Icon>
