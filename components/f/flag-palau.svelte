<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vymljlban.css';
import '../../css/c/c8er-hbku.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="vymljlban"/><circle class="c8er-hbku"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-palau" {...props}></Icon>
