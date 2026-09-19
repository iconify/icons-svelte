<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b487_1s0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="b487_1s0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:pencil-slash" {...props}></Icon>
