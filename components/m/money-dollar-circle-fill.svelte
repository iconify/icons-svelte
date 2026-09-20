<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu5jnmbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu5jnmbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:money-dollar-circle-fill" {...props}></Icon>
