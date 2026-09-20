<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za1mhnb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za1mhnb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:add-large-line" {...props}></Icon>
