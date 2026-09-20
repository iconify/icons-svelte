<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzippgsfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzippgsfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrow-down-right" {...props}></Icon>
