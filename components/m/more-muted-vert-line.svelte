<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqskjpbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqskjpbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-muted-vert-line" {...props}></Icon>
