<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz4p5n3yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sz4p5n3yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lucia" {...props}></Icon>
