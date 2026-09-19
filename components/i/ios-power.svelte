<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6a5nq_5m.css';
import '../../css/l/lw80oobkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h6a5nq_5m"/><path class="lw80oobkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-power" {...props}></Icon>
