<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd5f-k6hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd5f-k6hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:anytype" {...props}></Icon>
