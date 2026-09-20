<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l60z0rb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l60z0rb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bts" {...props}></Icon>
