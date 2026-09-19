<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o77mreb4u.css';
import '../../css/l/ljorwac7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o77mreb4u"/><path class="ljorwac7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-movie-play" {...props}></Icon>
