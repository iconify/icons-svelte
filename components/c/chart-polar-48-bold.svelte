<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icq3kqblj.css';
import '../../css/g/ga78bob5u.css';
import '../../css/p/pxeivcbuh.css';
import '../../css/q/q29j2bh-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="icq3kqblj"/><path class="ga78bob5u"/><path class="pxeivcbuh"/><path class="q29j2bh-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-polar-48-bold" {...props}></Icon>
