<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9_aw5bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k9_aw5bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chess-board" {...props}></Icon>
