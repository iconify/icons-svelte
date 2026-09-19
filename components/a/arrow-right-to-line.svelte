<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd98jnfaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kd98jnfaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-right-to-line" {...props}></Icon>
