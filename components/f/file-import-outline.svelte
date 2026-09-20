<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxtqwcadt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxtqwcadt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-import-outline" {...props}></Icon>
