<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj8p36bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj8p36bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:flashlight" {...props}></Icon>
