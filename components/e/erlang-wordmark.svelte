<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1w5x4bwa.css';
import '../../css/x/x46jw6bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="b1w5x4bwa"/><path class="x46jw6bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:erlang-wordmark" {...props}></Icon>
