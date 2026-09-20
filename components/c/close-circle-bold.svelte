<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv_eflodi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iv_eflodi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:close-circle-bold" {...props}></Icon>
