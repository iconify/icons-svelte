<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdo6r1bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdo6r1bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:printer-fill" {...props}></Icon>
