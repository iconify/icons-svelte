<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhk-rd3yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhk-rd3yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bookshelf-03" {...props}></Icon>
