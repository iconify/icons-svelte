<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isufo5b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isufo5b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:person-fill-24" {...props}></Icon>
