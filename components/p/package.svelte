<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb_frobnd.css';
import '../../css/l/l557xacfx.css';
import '../../css/q/qqhr9r1-v.css';
import '../../css/l/ljju7f6ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eb_frobnd"/><path class="l557xacfx"/><path class="qqhr9r1-v"/><path class="ljju7f6ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:package" {...props}></Icon>
