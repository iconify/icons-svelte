<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-2xq4bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-2xq4bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:gender-third" {...props}></Icon>
