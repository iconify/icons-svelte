<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j42lzccey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j42lzccey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diff-24" {...props}></Icon>
