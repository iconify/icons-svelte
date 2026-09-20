<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo9iqyb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo9iqyb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ren-py" {...props}></Icon>
