<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc0w28bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc0w28bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:octagon" {...props}></Icon>
