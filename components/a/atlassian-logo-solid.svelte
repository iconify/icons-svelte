<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk1l1r10t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vk1l1r10t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:atlassian-logo-solid" {...props}></Icon>
