<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0enz769b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0enz769b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ordered-list-filled" {...props}></Icon>
