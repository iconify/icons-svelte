<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_9o9ub1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_9o9ub1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:delphi" {...props}></Icon>
