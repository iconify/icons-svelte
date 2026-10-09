<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8xdzkbcj.css';
import '../../css/o/oky5uoojn.css';
import '../../css/s/swikctbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j8xdzkbcj"/><path class="oky5uoojn"/><path class="swikctbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:archive-48-bold" {...props}></Icon>
