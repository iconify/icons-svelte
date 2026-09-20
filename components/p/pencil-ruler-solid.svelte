<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5ezc0b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5ezc0b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pencil-ruler-solid" {...props}></Icon>
