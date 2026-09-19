<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmy9m9bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmy9m9bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:comment-add-bold" {...props}></Icon>
