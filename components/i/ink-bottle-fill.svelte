<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s450nebka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s450nebka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ink-bottle-fill" {...props}></Icon>
