<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/a/auswgj.css';
import '../../css/a/aunkjo.css';
import '../../css/s/so-from-40.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c auswgj"/><path class="a0m25c aunkjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:roundabout-left" {...props}></Icon>
