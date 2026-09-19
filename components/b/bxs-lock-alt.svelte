<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d71vq53qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d71vq53qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-lock-alt" {...props}></Icon>
