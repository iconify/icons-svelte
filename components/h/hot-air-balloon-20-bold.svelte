<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wupsqfb9m.css';
import '../../css/s/slmd-2blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wupsqfb9m"/><path class="slmd-2blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-air-balloon-20-bold" {...props}></Icon>
