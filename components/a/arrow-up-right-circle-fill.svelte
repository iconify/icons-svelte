<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_z1gpoxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s_z1gpoxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-right-circle-fill" {...props}></Icon>
