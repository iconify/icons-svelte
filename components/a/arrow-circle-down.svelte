<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3fflri5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="c3fflri5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-circle-down" {...props}></Icon>
