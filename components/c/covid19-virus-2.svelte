<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/t/th0y6sblu.css';
import '../../css/l/lidv3ugmq.css';
import '../../css/h/h160k9b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="th0y6sblu"/><path class="lidv3ugmq"/><path class="h160k9b-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:covid19-virus-2" {...props}></Icon>
