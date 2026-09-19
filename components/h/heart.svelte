<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwm-1ccgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwm-1ccgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:heart" {...props}></Icon>
