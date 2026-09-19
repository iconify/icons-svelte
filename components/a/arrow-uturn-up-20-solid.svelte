<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6apakbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l6apakbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-uturn-up-20-solid" {...props}></Icon>
