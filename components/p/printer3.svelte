<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p180r4b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p180r4b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:printer3" {...props}></Icon>
