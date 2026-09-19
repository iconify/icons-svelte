<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk-z4kbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wk-z4kbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:euro-solid" {...props}></Icon>
