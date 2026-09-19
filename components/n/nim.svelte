<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5bnq-jir.css';
import '../../css/j/j1uc_7b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l5bnq-jir"/><path class="j1uc_7b3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nim" {...props}></Icon>
