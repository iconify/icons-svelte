<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x33k3_bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x33k3_bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-haze-fill" {...props}></Icon>
