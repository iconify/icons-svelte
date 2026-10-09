<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-zna8aim.css';
import '../../css/q/qjyultakh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n-zna8aim"/><path class="qjyultakh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fusion-20" {...props}></Icon>
