<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqdezmpfc.css';
import '../../css/d/dqxdjrbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iqdezmpfc"/><path class="dqxdjrbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crimper-20" {...props}></Icon>
