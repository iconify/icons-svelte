<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfi5d0nul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfi5d0nul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:grid-24x24px-outline" {...props}></Icon>
