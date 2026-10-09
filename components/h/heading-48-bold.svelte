<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycu86rb2t.css';
import '../../css/m/my-nawb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ycu86rb2t"/><path class="my-nawb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heading-48-bold" {...props}></Icon>
