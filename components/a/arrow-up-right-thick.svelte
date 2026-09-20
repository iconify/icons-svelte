<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4bn97f2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4bn97f2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-right-thick" {...props}></Icon>
