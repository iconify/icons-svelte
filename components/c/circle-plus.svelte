<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/u/u1aoiyb0f.css';
import '../../css/a/aud40yyqp.css';
import '../../css/i/ikl0agb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="u1aoiyb0f"/><path class="aud40yyqp"/><path class="ikl0agb7y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:circle-plus" {...props}></Icon>
