<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0f-2ebpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0f-2ebpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aston-martin" {...props}></Icon>
