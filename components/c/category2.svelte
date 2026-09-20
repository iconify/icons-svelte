<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f63k4benb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f63k4benb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:category2" {...props}></Icon>
