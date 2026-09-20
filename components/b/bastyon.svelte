<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su9k-ubgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su9k-ubgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bastyon" {...props}></Icon>
