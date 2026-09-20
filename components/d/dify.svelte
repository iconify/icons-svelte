<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8yd1s8eo.css';
import '../../css/o/o0bjgebdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8yd1s8eo"/><path class="o0bjgebdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dify" {...props}></Icon>
