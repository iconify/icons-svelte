<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac7du0n2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac7du0n2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:chevron-double-down-outline" {...props}></Icon>
