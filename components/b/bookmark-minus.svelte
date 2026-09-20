<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4z83bxpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4z83bxpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:bookmark-minus" {...props}></Icon>
