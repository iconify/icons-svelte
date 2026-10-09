<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uspm4fblj.css';
import '../../css/b/bq1dbsvyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uspm4fblj"/><path class="bq1dbsvyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-down-left-48" {...props}></Icon>
