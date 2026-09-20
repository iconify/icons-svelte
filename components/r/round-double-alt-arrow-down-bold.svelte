<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj8ddjbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hj8ddjbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-double-alt-arrow-down-bold" {...props}></Icon>
