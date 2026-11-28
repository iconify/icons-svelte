<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcp3nyk7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary xcp3nyk7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-triple-down-duotone" {...props}></Icon>
