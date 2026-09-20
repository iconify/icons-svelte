<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze429bcme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ze429bcme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dice-20-solid" {...props}></Icon>
