<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex6kn_g6k.css';
import '../../css/s/s1dmhkb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ex6kn_g6k"/><path class="s1dmhkb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chef-knife-48" {...props}></Icon>
