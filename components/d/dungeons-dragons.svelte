<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc8pr7bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yc8pr7bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dungeons-dragons" {...props}></Icon>
