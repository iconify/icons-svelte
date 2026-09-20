<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lexve4bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lexve4bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-boarding-bullet-train-on-railway-track" {...props}></Icon>
