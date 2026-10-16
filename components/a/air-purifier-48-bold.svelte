<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svb9bze3d.css';
import '../../css/p/ps1xh1lfy.css';
import '../../css/c/czclwmg1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="svb9bze3d"/><path class="ps1xh1lfy"/><path class="czclwmg1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-purifier-48-bold" {...props}></Icon>
