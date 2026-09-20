<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-155s8pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-155s8pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:move-fill" {...props}></Icon>
