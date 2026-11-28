<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7op_oidd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7op_oidd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:rocking-chair-solid" {...props}></Icon>
