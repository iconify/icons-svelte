<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddli5yyid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddli5yyid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:list-filter-solid" {...props}></Icon>
