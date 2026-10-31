<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyk1s6ipo.css';
import '../../css/a/alb5d4f2o.css';
import '../../css/m/mar76sscm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="cyk1s6ipo"/><path class="alb5d4f2o"/><path class="mar76sscm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:bhutan" {...props}></Icon>
