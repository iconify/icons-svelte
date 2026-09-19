<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jku7b4b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jku7b4b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:format-underline" {...props}></Icon>
