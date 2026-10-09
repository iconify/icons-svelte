<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3p0zqbmw.css';
import '../../css/b/bl9mhqw5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b3p0zqbmw"/><path class="bl9mhqw5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pool-48-bold" {...props}></Icon>
