<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwlomdbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwlomdbcu primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-dashed-minus-duotone" {...props}></Icon>
