<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb6_mlbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pb6_mlbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h5-20-solid" {...props}></Icon>
