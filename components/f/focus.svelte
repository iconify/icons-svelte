<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyaa94bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyaa94bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:focus" {...props}></Icon>
