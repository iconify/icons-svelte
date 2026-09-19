<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqoqyjb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="xqoqyjb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-full-stroke-16" {...props}></Icon>
