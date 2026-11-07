<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm9z_7bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pm9z_7bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:car-20-solid" {...props}></Icon>
