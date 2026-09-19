<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/fd-ahacbo.css';
import '../../css/j/joa4c8oic.css';
import '../../css/e/eaxacq3vs.css';
import '../../css/b/b8ccrhvkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><rect class="fd-ahacbo"/><rect class="joa4c8oic"/><rect class="eaxacq3vs"/><rect class="b8ccrhvkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:apps" {...props}></Icon>
