<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy6voyb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy6voyb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:discount-list-filled" {...props}></Icon>
