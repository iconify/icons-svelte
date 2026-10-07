<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjlihvj4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjlihvj4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:query-pagination-next" {...props}></Icon>
