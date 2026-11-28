<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz-h02jqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz-h02jqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:plate" {...props}></Icon>
