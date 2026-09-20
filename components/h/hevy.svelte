<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv51zcb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv51zcb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hevy" {...props}></Icon>
