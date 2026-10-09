<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7kb9t1gf.css';
import '../../css/f/fj-2afnlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s7kb9t1gf"/><path class="fj-2afnlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-down-left-48-bold" {...props}></Icon>
