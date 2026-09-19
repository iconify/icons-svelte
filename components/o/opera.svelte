<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jma18ccud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jma18ccud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:opera" {...props}></Icon>
