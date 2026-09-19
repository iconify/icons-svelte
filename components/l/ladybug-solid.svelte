<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxn-31-fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oxn-31-fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:ladybug-solid" {...props}></Icon>
