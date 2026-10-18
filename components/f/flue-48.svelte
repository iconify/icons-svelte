<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghoh098lm.css';
import '../../css/n/nyhx7fbbv.css';
import '../../css/z/zxrbw5bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ghoh098lm"/><path class="nyhx7fbbv"/><path class="zxrbw5bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flue-48" {...props}></Icon>
