<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjufl_hsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjufl_hsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folder-plus" {...props}></Icon>
