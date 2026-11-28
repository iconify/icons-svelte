<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek3vm84wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek3vm84wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-spreadsheet-plus" {...props}></Icon>
