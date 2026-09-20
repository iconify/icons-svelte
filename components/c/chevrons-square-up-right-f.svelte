<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zri5nhecr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="zri5nhecr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-square-up-right-f" {...props}></Icon>
