<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1w0d8d4j.css';
import '../../css/i/i0y7ncbnv.css';
import '../../css/t/t8dqc66mp.css';
import '../../css/p/pwmnyqitk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p1w0d8d4j"/><path class="i0y7ncbnv"/><path class="t8dqc66mp"/><path class="pwmnyqitk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:building-x-48" {...props}></Icon>
