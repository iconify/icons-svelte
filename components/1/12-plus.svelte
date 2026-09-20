<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzu5dbbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzu5dbbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:12-plus" {...props}></Icon>
