<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds95o_99b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds95o_99b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jdoodle" {...props}></Icon>
