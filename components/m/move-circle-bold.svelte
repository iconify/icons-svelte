<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8xtb3bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8xtb3bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-circle-bold" {...props}></Icon>
