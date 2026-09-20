<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igjvtxb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="igjvtxb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:3d-box-fill" {...props}></Icon>
