<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4vli7ncu.css';
import '../../css/q/qkvjsbbnn.css';
import '../../css/k/klpkadckn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j4vli7ncu"/><path class="qkvjsbbnn"/><path class="klpkadckn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-donut-48-bold" {...props}></Icon>
