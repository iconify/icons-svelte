<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7fq4xbnr.css';
import '../../css/w/wg5_tobjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7fq4xbnr"/><path class="wg5_tobjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:passport-1" {...props}></Icon>
