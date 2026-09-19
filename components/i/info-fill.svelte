<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx9_5y40s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx9_5y40s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:info-fill" {...props}></Icon>
