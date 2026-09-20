<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3flg03kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b3flg03kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:full-screen-bold" {...props}></Icon>
