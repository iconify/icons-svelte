<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8nc87u9j.css';
import '../../css/w/w7okmzx7d.css';
import '../../css/k/kxc6azbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z8nc87u9j"/><path class="w7okmzx7d"/><path class="kxc6azbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-blending-48" {...props}></Icon>
