<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py6-88b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="py6-88b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:embed-audio" {...props}></Icon>
