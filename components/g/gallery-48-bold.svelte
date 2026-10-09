<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p96uvcb3z.css';
import '../../css/h/hpajvh8ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p96uvcb3z"/><path class="hpajvh8ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gallery-48-bold" {...props}></Icon>
