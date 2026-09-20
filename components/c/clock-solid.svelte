<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjvvb2byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjvvb2byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:clock-solid" {...props}></Icon>
