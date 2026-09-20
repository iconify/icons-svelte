<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/s/sx312ii4d.css';
import '../../css/h/h5q8bi3ys.css';
import '../../css/z/zbrg6qx3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sx312ii4d"/><path class="h5q8bi3ys"/><path class="zbrg6qx3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:eye-slash" {...props}></Icon>
