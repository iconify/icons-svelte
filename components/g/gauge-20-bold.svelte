<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbw4lkb5b.css';
import '../../css/o/o45kaobgy.css';
import '../../css/q/q38qvzq1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kbw4lkb5b"/><path class="o45kaobgy"/><path class="q38qvzq1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gauge-20-bold" {...props}></Icon>
