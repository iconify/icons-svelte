<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be1bswbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be1bswbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:gem-star" {...props}></Icon>
