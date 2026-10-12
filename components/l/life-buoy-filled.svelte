<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x45pw7zuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x45pw7zuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:life-buoy-filled" {...props}></Icon>
