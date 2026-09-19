<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1319_4lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h1319_4lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-quote" {...props}></Icon>
