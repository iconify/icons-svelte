<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttzf9xspn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttzf9xspn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:landmark" {...props}></Icon>
