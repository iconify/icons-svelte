<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_3lq3b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_3lq3b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-right-circle-solid" {...props}></Icon>
