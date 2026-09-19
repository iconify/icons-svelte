<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_igqwtua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_igqwtua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-2-solid" {...props}></Icon>
