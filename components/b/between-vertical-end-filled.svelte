<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykz2nk03s.css';
import '../../css/w/w4_yefglu.css';
import '../../css/a/ag06jb7os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykz2nk03s"/><rect class="w4_yefglu"/><rect class="ag06jb7os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:between-vertical-end-filled" {...props}></Icon>
