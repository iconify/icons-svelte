<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcny2x1-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcny2x1-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-square-filled" {...props}></Icon>
