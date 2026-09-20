<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/n/nw21fqb1s.css';
import '../../css/r/r9hyg7b7k.css';
import '../../css/p/p9-zrkb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nw21fqb1s"/><path class="r9hyg7b7k"/><path class="p9-zrkb4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bucket-circle2-filled" {...props}></Icon>
