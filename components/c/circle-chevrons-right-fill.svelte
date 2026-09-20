<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjle34-cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjle34-cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-chevrons-right-fill" {...props}></Icon>
