<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhgalibbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dhgalibbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:globe-fill-12" {...props}></Icon>
