<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-73xxboi.css';
import '../../css/a/as12j9bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g-73xxboi"/><path class="as12j9bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bell-strike-stroke-20" {...props}></Icon>
