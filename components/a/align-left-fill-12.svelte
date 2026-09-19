<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdz-l3bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kdz-l3bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-left-fill-12" {...props}></Icon>
