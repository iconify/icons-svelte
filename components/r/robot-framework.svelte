<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd3rj95lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd3rj95lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:robot-framework" {...props}></Icon>
