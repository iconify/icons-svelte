<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo0s-wbvc.css';
import '../../css/t/t0ztzgb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lo0s-wbvc"/><path class="t0ztzgb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-open-20" {...props}></Icon>
