<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsdo12b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsdo12b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:kinopoisk" {...props}></Icon>
