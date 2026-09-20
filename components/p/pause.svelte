<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mktyztbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mktyztbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:pause" {...props}></Icon>
