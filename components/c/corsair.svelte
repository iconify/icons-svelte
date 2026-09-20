<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rczt1zc3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rczt1zc3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:corsair" {...props}></Icon>
