<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr1y3kbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pr1y3kbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-rupee-solid" {...props}></Icon>
