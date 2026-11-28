<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-3k0obzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary q-3k0obzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-triple-up-duotone" {...props}></Icon>
