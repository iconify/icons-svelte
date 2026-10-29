<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2d5gq9iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2d5gq9iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-chevron-down-solid" {...props}></Icon>
