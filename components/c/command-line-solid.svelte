<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r68vbdzvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r68vbdzvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:command-line-solid" {...props}></Icon>
