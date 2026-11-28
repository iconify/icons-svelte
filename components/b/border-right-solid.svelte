<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/url7r030e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="url7r030e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:border-right-solid" {...props}></Icon>
