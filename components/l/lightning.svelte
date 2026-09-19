<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8ehmpvfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="y8ehmpvfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:lightning" {...props}></Icon>
