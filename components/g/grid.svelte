<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg7ftebsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg7ftebsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid" {...props}></Icon>
