<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo1il0bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lo1il0bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:na" {...props}></Icon>
