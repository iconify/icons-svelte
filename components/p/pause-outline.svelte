<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9p3ynbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p9p3ynbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:pause-outline" {...props}></Icon>
