<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjk8aukoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjk8aukoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-4-fill" {...props}></Icon>
