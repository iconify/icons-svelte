<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcootiqyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pcootiqyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-uturn-left-solid" {...props}></Icon>
