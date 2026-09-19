<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n44tryb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n44tryb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:crop" {...props}></Icon>
