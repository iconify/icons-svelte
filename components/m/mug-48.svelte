<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4kijcj5b.css';
import '../../css/t/tea15-vcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d4kijcj5b"/><path class="tea15-vcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mug-48" {...props}></Icon>
