<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1ws80bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary w1ws80bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:rose-duotone" {...props}></Icon>
