<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk5tax74a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk5tax74a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:loader-2-fill" {...props}></Icon>
