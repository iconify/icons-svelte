<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgw5nzbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgw5nzbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-left-bar" {...props}></Icon>
