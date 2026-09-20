<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nczzpqi_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nczzpqi_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-left-right-20-solid" {...props}></Icon>
