<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3mbkdb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p3mbkdb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h4-20-solid" {...props}></Icon>
