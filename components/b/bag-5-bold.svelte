<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyzb478mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iyzb478mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-5-bold" {...props}></Icon>
