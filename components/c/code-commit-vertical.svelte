<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr82g6bod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr82g6bod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:code-commit-vertical" {...props}></Icon>
