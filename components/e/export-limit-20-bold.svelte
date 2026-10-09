<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljun7bd8t.css';
import '../../css/y/yk5jtlbyy.css';
import '../../css/w/wj33zbcyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ljun7bd8t"/><path class="yk5jtlbyy"/><path class="wj33zbcyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:export-limit-20-bold" {...props}></Icon>
