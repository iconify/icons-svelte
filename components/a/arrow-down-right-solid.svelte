<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw11da53d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rw11da53d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-right-solid" {...props}></Icon>
