<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu1u67bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":850};
const content = `<path class="eu1u67bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:linkedin" {...props}></Icon>
