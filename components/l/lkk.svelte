<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o06v5dbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o06v5dbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:lkk" {...props}></Icon>
