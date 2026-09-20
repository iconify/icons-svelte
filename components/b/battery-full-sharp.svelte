<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4zkhxbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4zkhxbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:battery-full-sharp" {...props}></Icon>
