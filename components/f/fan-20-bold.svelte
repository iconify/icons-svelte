<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp_dhhbys.css';
import '../../css/e/ewqmb9jcq.css';
import '../../css/h/hizyf0byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cp_dhhbys"/><path class="ewqmb9jcq"/><path class="hizyf0byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fan-20-bold" {...props}></Icon>
