<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcn5mccjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcn5mccjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kongregate" {...props}></Icon>
