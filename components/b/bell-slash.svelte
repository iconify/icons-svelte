<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8ks_pb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8ks_pb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell-slash" {...props}></Icon>
