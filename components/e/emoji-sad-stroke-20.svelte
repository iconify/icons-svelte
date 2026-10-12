<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yynfaacui.css';
import '../../css/g/g6pvh7b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yynfaacui"/><path class="g6pvh7b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:emoji-sad-stroke-20" {...props}></Icon>
