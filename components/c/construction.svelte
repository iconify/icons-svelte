<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ripm6yrej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ripm6yrej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:construction" {...props}></Icon>
