<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbolzgbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbolzgbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chevron-duo-right" {...props}></Icon>
