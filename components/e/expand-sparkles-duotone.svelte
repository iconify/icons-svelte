<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohjgf69hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohjgf69hh primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:expand-sparkles-duotone" {...props}></Icon>
