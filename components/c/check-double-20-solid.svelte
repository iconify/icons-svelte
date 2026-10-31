<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwxonpa1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gwxonpa1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:check-double-20-solid" {...props}></Icon>
