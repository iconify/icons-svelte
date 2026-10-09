<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc95n_4_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mc95n_4_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-left-20" {...props}></Icon>
