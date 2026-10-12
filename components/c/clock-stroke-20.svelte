<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yynfaacui.css';
import '../../css/w/wyyg1obun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yynfaacui"/><path class="wyyg1obun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-stroke-20" {...props}></Icon>
