<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmh1bfs7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmh1bfs7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:dot-01-xs" {...props}></Icon>
