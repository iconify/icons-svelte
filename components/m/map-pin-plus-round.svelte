<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9t076bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9t076bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:map-pin-plus-round" {...props}></Icon>
