<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqsqo9bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqsqo9bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:bell-plus" {...props}></Icon>
