<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vukmlib7r.css';
import '../../css/e/e31pe1ygs.css';
import '../../css/q/qw45uljby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vukmlib7r"/><path class="e31pe1ygs"/><path class="qw45uljby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-9v-20" {...props}></Icon>
