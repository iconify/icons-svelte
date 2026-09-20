<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo7q9nu5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bo7q9nu5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:creative-commons" {...props}></Icon>
