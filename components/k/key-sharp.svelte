<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy9ew3n9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vy9ew3n9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:key-sharp" {...props}></Icon>
