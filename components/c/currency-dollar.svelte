<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjhz6wbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjhz6wbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-dollar" {...props}></Icon>
