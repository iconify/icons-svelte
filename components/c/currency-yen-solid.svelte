<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0g43yble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i0g43yble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-yen-solid" {...props}></Icon>
