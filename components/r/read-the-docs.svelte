<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpspazbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpspazbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:read-the-docs" {...props}></Icon>
