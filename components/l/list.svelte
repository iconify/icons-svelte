<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/b/b_3n6ybgo.css';
import '../../css/a/aozhopb2y.css';
import '../../css/f/fhv7l6bvd.css';
import '../../css/e/edjtn2bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="b_3n6ybgo"/><path class="aozhopb2y"/><path class="fhv7l6bvd"/><path class="edjtn2bks"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:list" {...props}></Icon>
