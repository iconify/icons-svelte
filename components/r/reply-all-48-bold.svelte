<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6pg-hzok.css';
import '../../css/i/i8cbj5bwx.css';
import '../../css/o/o-urmp0yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r6pg-hzok"/><path class="i8cbj5bwx"/><path class="o-urmp0yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:reply-all-48-bold" {...props}></Icon>
