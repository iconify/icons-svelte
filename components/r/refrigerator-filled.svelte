<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1ooaw6hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1ooaw6hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:refrigerator-filled" {...props}></Icon>
