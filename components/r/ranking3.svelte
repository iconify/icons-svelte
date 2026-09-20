<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff6e6iscy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff6e6iscy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ranking3" {...props}></Icon>
