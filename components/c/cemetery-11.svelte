<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztnzy1bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ztnzy1bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:cemetery-11" {...props}></Icon>
