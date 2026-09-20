<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukxbgsb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukxbgsb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:jewish-star-filled" {...props}></Icon>
