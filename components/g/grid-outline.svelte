<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6f47mbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6f47mbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:grid-outline" {...props}></Icon>
