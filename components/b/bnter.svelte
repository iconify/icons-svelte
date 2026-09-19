<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frctqbb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="frctqbb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:bnter" {...props}></Icon>
