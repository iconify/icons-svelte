<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk1ek6bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tk1ek6bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:check-mark" {...props}></Icon>
