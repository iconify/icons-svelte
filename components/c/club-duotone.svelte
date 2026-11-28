<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx1599bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary tx1599bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:club-duotone" {...props}></Icon>
