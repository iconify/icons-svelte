<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufmo4-xzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1792};
const content = `<path class="ufmo4-xzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:id-badge" {...props}></Icon>
