<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llo9xcgaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llo9xcgaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:greenhouse" {...props}></Icon>
