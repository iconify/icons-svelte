<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyrpv8pvm.css';
import '../../css/o/o8g693dbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zyrpv8pvm"/><path class="o8g693dbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dashboard-20" {...props}></Icon>
