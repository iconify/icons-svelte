<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t85jj0bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t85jj0bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-account-outline" {...props}></Icon>
