<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5xa376xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5xa376xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:export-fill" {...props}></Icon>
