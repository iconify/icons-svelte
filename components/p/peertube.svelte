<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7trfy.css';
import '../../css/y/yfo60c.css';
import '../../css/b/botfzx.css';
import '../../css/d/d-tbwzce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGOgwoJbQI"><path class="g7trfy"/><path class="yfo60c"/></mask></defs><path mask="url(#SVGOgwoJbQI)" class="botfzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:peertube" {...props}></Icon>
