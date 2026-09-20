<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faofj7wie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="faofj7wie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fritz" {...props}></Icon>
