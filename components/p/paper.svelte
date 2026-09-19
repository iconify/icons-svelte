<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6atuyb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6atuyb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:paper" {...props}></Icon>
