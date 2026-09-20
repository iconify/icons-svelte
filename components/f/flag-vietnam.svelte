<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8cxt48ie.css';
import '../../css/m/mdbtpac8h.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="e8cxt48ie"/><path class="mdbtpac8h"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-vietnam" {...props}></Icon>
