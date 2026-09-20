<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd1ss3b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zd1ss3b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:information-circle-remix" {...props}></Icon>
