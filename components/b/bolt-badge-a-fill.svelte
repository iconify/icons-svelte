<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei6n3ebmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ei6n3ebmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bolt-badge-a-fill" {...props}></Icon>
