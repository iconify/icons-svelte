<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agp85jbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agp85jbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cadillac" {...props}></Icon>
