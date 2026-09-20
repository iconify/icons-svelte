<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8vl9qb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8vl9qb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:overleaf" {...props}></Icon>
