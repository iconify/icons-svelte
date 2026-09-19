<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp0we2b3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cp0we2b3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:inbox-full-solid" {...props}></Icon>
