<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnv8y4ccs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="hnv8y4ccs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:circle-o" {...props}></Icon>
