<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewqmb9jcq.css';
import '../../css/g/gykt9mb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewqmb9jcq"/><path class="gykt9mb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rotor-20-bold" {...props}></Icon>
