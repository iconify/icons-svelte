<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9xtaw1ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9xtaw1ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:ellipses-horizontal-solid" {...props}></Icon>
