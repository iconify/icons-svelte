<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/gcicxwbvy.css';
import '../../css/o/opt7t5xjr.css';
import '../../css/x/x03iucczk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gcicxwbvy"/><path class="opt7t5xjr"/><path class="x03iucczk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:covid-carrier-packages" {...props}></Icon>
