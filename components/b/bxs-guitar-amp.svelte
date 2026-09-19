<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7pmgsrcq.css';
import '../../css/a/ar62u3ixi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7pmgsrcq"/><path class="ar62u3ixi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-guitar-amp" {...props}></Icon>
