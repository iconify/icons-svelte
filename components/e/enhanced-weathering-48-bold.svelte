<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjzh0acdq.css';
import '../../css/x/xj3pm5bqn.css';
import '../../css/c/ccxgjdu-m.css';
import '../../css/t/tz2duac5o.css';
import '../../css/w/w3qsn0byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mjzh0acdq"/><path class="xj3pm5bqn"/><path class="ccxgjdu-m"/><path class="tz2duac5o"/><path class="w3qsn0byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:enhanced-weathering-48-bold" {...props}></Icon>
