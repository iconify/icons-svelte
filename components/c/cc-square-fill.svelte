<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x61k8684r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x61k8684r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cc-square-fill" {...props}></Icon>
