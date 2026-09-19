<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meftk6b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="meftk6b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-lines-outline" {...props}></Icon>
