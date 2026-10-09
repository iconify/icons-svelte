<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h34p0iehr.css';
import '../../css/z/zab0-ccwk.css';
import '../../css/b/b-mdupdvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h34p0iehr"/><path class="zab0-ccwk"/><path class="b-mdupdvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:quote-48" {...props}></Icon>
