<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_j8j347h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_j8j347h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:card-view-tiles" {...props}></Icon>
