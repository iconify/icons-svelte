<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve5kkwb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ve5kkwb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:pray" {...props}></Icon>
