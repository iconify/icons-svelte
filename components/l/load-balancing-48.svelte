<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6a66hhkg.css';
import '../../css/h/h2yezpf2d.css';
import '../../css/e/ev4sdmbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q6a66hhkg"/><path class="h2yezpf2d"/><path class="ev4sdmbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:load-balancing-48" {...props}></Icon>
