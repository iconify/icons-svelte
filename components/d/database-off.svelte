<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3h3o9jjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3h3o9jjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:database-off" {...props}></Icon>
