<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j45atcbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j45atcbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:close-circle" {...props}></Icon>
