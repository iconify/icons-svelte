<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws0nytbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws0nytbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:embark" {...props}></Icon>
