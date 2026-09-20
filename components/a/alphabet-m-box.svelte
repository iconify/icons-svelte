<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvlax3sde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvlax3sde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-m-box" {...props}></Icon>
