<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqir62biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bqir62biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cyborg-2-remix" {...props}></Icon>
