<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnvxjnbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnvxjnbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:adjustments-vertical-solid" {...props}></Icon>
