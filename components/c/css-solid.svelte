<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfjiz2bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfjiz2bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:css-solid" {...props}></Icon>
