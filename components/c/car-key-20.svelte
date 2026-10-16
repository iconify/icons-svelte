<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyz2lacbc.css';
import '../../css/g/g51el4b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lyz2lacbc"/><path class="g51el4b_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:car-key-20" {...props}></Icon>
