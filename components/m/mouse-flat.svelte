<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bgdc7hbhx.css';
import '../../css/i/ik-9ob1vk.css';
import '../../css/f/ffeeo3bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="bgdc7hbhx"/><path class="ik-9ob1vk"/><path clip-rule="evenodd" class="ffeeo3bqd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:mouse-flat" {...props}></Icon>
