<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-07p3bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-07p3bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:database" {...props}></Icon>
