<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a829lwbpl.css';
import '../../css/n/nk1pwkb6d.css';
import '../../css/h/haixszbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a829lwbpl"/><path class="nk1pwkb6d"/><path class="haixszbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lockout-48" {...props}></Icon>
