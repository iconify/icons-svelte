<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzq6zreob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="lzq6zreob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:graphql" {...props}></Icon>
