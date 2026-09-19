<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyn6rc_-u.css';
import '../../css/j/j_ie9rx3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyn6rc_-u"/><ellipse class="j_ie9rx3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-sushi" {...props}></Icon>
