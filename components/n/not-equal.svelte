<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knfpyxbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knfpyxbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:not-equal" {...props}></Icon>
