<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0ddzjb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0ddzjb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-remove" {...props}></Icon>
