<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su2fj2bbc.css';
import '../../css/k/ksiw30c1e.css';
import '../../css/g/g8-7we8zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="su2fj2bbc"/><path class="ksiw30c1e"/><path class="g8-7we8zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:leaf-check-20" {...props}></Icon>
