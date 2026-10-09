<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsveq9qwk.css';
import '../../css/j/jfh5rkbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tsveq9qwk"/><path class="jfh5rkbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pram-48-bold" {...props}></Icon>
