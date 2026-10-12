<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yynfaacui.css';
import '../../css/t/tqme7yb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yynfaacui"/><path class="tqme7yb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:question-mark-circle-stroke-20" {...props}></Icon>
