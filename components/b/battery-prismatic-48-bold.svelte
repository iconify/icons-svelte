<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kblqbnvqy.css';
import '../../css/t/timwp37xc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kblqbnvqy"/><path class="timwp37xc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-prismatic-48-bold" {...props}></Icon>
