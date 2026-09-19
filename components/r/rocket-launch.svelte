<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um0m0ubvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um0m0ubvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:rocket-launch" {...props}></Icon>
