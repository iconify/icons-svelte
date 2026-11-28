<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au7bzabxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au7bzabxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:image-arrow-down" {...props}></Icon>
