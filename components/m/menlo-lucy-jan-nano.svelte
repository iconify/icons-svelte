<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8fa9u_0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8fa9u_0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:menlo-lucy-jan-nano" {...props}></Icon>
