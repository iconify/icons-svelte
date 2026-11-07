<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2a0f5bgc.css';
import '../../css/m/mao0_zbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2a0f5bgc"/><path class="mao0_zbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:circle-bottom-up-bold" {...props}></Icon>
