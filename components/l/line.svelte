<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-j2nt4-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":684,"height":677};
const content = `<path class="t-j2nt4-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:line" {...props}></Icon>
