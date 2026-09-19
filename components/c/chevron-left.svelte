<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm3k6z7iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mm3k6z7iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:chevron-left" {...props}></Icon>
