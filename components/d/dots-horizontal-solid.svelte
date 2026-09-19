<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9bzb7gtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9bzb7gtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:dots-horizontal-solid" {...props}></Icon>
