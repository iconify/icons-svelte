<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc8qyybol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc8qyybol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-open-2-fill" {...props}></Icon>
