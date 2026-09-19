<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8h9a8w2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8h9a8w2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:circle-half" {...props}></Icon>
