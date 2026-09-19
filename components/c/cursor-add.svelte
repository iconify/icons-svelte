<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j62ez0b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j62ez0b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cursor-add" {...props}></Icon>
