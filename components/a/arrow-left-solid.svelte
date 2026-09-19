<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg_hf-5gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mg_hf-5gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-left-solid" {...props}></Icon>
