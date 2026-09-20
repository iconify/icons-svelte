<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4h4um1rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4h4um1rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:csv" {...props}></Icon>
