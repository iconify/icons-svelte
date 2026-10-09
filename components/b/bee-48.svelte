<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppl_-uorl.css';
import '../../css/u/uso6srbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ppl_-uorl"/><path class="uso6srbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bee-48" {...props}></Icon>
