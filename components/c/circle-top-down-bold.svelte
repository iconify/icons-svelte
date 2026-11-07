<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh-3ee_ik.css';
import '../../css/e/ecbj7fz0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sh-3ee_ik"/><path class="ecbj7fz0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:circle-top-down-bold" {...props}></Icon>
