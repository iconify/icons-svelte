<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k13mh-w9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k13mh-w9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:arrow-up-right-down-left-outline" {...props}></Icon>
