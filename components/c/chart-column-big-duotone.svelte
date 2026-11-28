<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6hb1eb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6hb1eb2s primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-column-big-duotone" {...props}></Icon>
