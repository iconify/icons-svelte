<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzqmbeoxz.css';
import '../../css/b/bve3o65en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzqmbeoxz"/><path class="bve3o65en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:leaf-2-line" {...props}></Icon>
