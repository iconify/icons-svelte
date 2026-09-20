<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d60hbwahx.css';
import '../../css/c/cnqq36xqp.css';
import '../../css/z/zunq1wbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":120,"height":120};
const content = `<g class="d60hbwahx"><path clip-rule="evenodd" class="cnqq36xqp"/><path class="zunq1wbfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:refine-light" {...props}></Icon>
