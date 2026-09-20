<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lke22-_uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lke22-_uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:flask-conical" {...props}></Icon>
