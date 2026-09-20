<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd1kpyb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd1kpyb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:h3" {...props}></Icon>
