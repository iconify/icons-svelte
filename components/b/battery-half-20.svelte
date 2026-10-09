<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkwocjb5q.css';
import '../../css/h/hhg2zab-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mkwocjb5q"/><path class="hhg2zab-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-half-20" {...props}></Icon>
