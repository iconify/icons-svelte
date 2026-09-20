<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g171l-c8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g171l-c8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-plus" {...props}></Icon>
