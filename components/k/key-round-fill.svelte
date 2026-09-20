<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pafxnwblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pafxnwblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:key-round-fill" {...props}></Icon>
