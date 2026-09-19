<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-sd3vb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":44,"height":24};
const content = `<path clip-rule="evenodd" class="y-sd3vb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:button" {...props}></Icon>
