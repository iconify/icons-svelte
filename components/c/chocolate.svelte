<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2ouo0buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2ouo0buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chocolate" {...props}></Icon>
