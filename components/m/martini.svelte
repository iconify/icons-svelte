<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/u/u14h2nnim.css';
import '../../css/j/jv0fhacxo.css';
import '../../css/b/bg79nabpd.css';
import '../../css/m/mq7rj2aqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="u14h2nnim wm-shadow"/><path class="jv0fhacxo wm-shadow"/><path class="bg79nabpd"/><path class="mq7rj2aqp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:martini" {...props}></Icon>
