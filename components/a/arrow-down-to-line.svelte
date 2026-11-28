<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/saij5kb4t.css';
import '../../css/n/n3xvoccbk.css';
import '../../css/t/te09yrbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="saij5kb4t"/><path class="n3xvoccbk"/><path class="te09yrbly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-to-line" {...props}></Icon>
