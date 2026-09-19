<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m009m8q_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m009m8q_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:flick-up" {...props}></Icon>
