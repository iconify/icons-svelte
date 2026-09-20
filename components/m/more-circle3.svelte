<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab2by8v5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab2by8v5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:more-circle3" {...props}></Icon>
