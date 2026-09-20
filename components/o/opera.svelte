<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3-9t806r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3-9t806r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:opera" {...props}></Icon>
