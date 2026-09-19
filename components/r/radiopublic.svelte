<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoj__nbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yoj__nbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:radiopublic" {...props}></Icon>
