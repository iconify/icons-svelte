<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on_0wn7zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on_0wn7zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-up-from-line" {...props}></Icon>
