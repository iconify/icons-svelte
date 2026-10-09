<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef455w1yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ef455w1yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:navigation-off-48-bold" {...props}></Icon>
