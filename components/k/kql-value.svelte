<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjofvhbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wjofvhbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:kql-value" {...props}></Icon>
