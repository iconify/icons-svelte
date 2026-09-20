<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y02t58mry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y02t58mry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:duplicati" {...props}></Icon>
