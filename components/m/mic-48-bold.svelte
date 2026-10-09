<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu7f3lbhq.css';
import '../../css/f/fzl-y-qur.css';
import '../../css/b/bg9q4obqt.css';
import '../../css/q/qpoqx3b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yu7f3lbhq"/><path class="fzl-y-qur"/><path class="bg9q4obqt"/><path class="qpoqx3b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mic-48-bold" {...props}></Icon>
