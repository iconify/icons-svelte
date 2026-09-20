<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv7d94b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv7d94b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:category" {...props}></Icon>
