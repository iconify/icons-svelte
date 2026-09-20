<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpxhp8q3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpxhp8q3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-arrow-down" {...props}></Icon>
