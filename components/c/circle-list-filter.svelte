<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/q/qjj74mrlx.css';
import '../../css/c/c4420yblp.css';
import '../../css/t/tdpocnguc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ud95brdct"/><path class="qjj74mrlx"/><path class="c4420yblp"/><path class="tdpocnguc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-list-filter" {...props}></Icon>
