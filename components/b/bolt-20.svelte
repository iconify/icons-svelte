<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-v3z0_fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q-v3z0_fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-20" {...props}></Icon>
