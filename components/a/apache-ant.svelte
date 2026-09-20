<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaqfuab8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yaqfuab8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache-ant" {...props}></Icon>
