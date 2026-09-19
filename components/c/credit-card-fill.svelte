<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_z_be-dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t_z_be-dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:credit-card-fill" {...props}></Icon>
