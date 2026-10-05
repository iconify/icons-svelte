<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/x/xem9_test.css';
import '../../css/e/e2nzkvbqx.css';
import '../../css/b/b-rxv4bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="xem9_test"/><path class="e2nzkvbqx"/><path class="b-rxv4bhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:home" {...props}></Icon>
