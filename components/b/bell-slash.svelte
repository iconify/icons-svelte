<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiripzknj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xiripzknj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:bell-slash" {...props}></Icon>
