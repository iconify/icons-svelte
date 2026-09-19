<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h77rvsg5y.css';
import '../../css/c/csorej16m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h77rvsg5y"/><path class="csorej16m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-angular" {...props}></Icon>
