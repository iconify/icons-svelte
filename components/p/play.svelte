<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j57x0ccea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j57x0ccea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:play" {...props}></Icon>
