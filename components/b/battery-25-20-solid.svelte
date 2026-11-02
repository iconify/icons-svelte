<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhriw0pwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bhriw0pwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:battery-25-20-solid" {...props}></Icon>
