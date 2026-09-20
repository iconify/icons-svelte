<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge0c7ebqz.css';
import '../../css/d/dabr2tbbh.css';
import '../../css/j/j5ohattzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ge0c7ebqz"/><path clip-rule="evenodd" class="dabr2tbbh"/><path class="j5ohattzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:mortarboard-fill" {...props}></Icon>
