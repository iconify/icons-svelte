<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9jn-l41s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9jn-l41s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:rotate-right-filled" {...props}></Icon>
