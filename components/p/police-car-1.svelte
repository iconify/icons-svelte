<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwoh2zb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwoh2zb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:police-car-1" {...props}></Icon>
