<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o76mt6y5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o76mt6y5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hotdog-solid" {...props}></Icon>
