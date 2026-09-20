<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krnc8kyjp.css';
import '../../css/f/f0fcqmbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krnc8kyjp"/><path class="f0fcqmbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:comment-dots" {...props}></Icon>
