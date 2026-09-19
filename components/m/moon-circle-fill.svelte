<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0_g8l7oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="s0_g8l7oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:moon-circle-fill" {...props}></Icon>
