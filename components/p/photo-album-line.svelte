<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl61vjbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl61vjbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:photo-album-line" {...props}></Icon>
