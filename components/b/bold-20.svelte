<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_4nbxblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f_4nbxblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bold-20" {...props}></Icon>
