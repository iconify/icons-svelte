<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztcz48ldh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ztcz48ldh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:battery-most-solid" {...props}></Icon>
