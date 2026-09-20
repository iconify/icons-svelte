<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chwl8y35o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chwl8y35o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chevron-up" {...props}></Icon>
