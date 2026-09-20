<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we_6prbbh.css';
import '../../css/c/ck8dpqbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="we_6prbbh"/><path clip-rule="evenodd" class="ck8dpqbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:question-12" {...props}></Icon>
