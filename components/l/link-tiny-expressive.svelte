<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5q01fe6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5q01fe6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:link-tiny-expressive" {...props}></Icon>
