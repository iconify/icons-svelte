<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-fjlabhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-fjlabhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:caret-up-outline" {...props}></Icon>
