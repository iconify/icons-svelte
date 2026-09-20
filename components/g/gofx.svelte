<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdwx1s0ae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdwx1s0ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gofx" {...props}></Icon>
