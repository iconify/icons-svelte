<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw-t5bcty.css';
import '../../css/d/dqolik5wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xw-t5bcty"/><path class="dqolik5wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bbq-48-bold" {...props}></Icon>
