<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh2uq7v6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh2uq7v6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:adjustments-horizontal" {...props}></Icon>
