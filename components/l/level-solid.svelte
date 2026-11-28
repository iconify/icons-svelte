<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x212_9lqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x212_9lqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:level-solid" {...props}></Icon>
