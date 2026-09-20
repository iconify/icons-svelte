<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4v71-79i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4v71-79i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:link-square3-filled" {...props}></Icon>
