<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag2su0b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag2su0b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:caret-up-md" {...props}></Icon>
