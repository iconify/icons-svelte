<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yynd6vbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yynd6vbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase-search-outline" {...props}></Icon>
