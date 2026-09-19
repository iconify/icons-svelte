<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5-6tkbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5-6tkbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:reflect-vertical-alt" {...props}></Icon>
