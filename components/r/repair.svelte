<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkvi805gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bkvi805gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:repair" {...props}></Icon>
