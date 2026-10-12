<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yynfaacui.css';
import '../../css/t/tbe9gjgli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yynfaacui"/><path class="tbe9gjgli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:emoji-neutral-stroke-20" {...props}></Icon>
