<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh0fu8bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wh0fu8bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:code-pull-request-solid" {...props}></Icon>
