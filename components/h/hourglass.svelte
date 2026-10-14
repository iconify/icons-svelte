<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/k/k_6msqblp.css';
import '../../css/x/x39lywbmx.css';
import '../../css/c/cmekjibeu.css';
import '../../css/x/x9lf62b7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="k_6msqblp"/><path class="x39lywbmx"/><path class="cmekjibeu"/><path class="x9lf62b7r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:hourglass" {...props}></Icon>
