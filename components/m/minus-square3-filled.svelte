<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzr5fjb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzr5fjb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:minus-square3-filled" {...props}></Icon>
