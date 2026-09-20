<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bin4q55ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bin4q55ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:plane-takeoff-sharp" {...props}></Icon>
