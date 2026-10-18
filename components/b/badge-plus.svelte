<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq2epzunt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq2epzunt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:badge-plus" {...props}></Icon>
