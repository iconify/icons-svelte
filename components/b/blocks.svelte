<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu279i0ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu279i0ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:blocks" {...props}></Icon>
