<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w63goej-d.css';
import '../../css/z/zqrgw3bcs.css';
import '../../css/s/s1299sedn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w63goej-d"/><path class="zqrgw3bcs"/><path class="s1299sedn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drone-inspection-48-bold" {...props}></Icon>
