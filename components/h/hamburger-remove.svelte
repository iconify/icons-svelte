<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3cif1uvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3cif1uvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hamburger-remove" {...props}></Icon>
