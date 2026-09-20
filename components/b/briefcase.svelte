<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8opnib-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h8opnib-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:briefcase" {...props}></Icon>
