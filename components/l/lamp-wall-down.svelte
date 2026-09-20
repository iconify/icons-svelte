<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzqvqw61x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzqvqw61x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:lamp-wall-down" {...props}></Icon>
