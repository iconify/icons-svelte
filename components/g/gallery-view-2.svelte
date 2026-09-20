<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtbaj_b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtbaj_b3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gallery-view-2" {...props}></Icon>
