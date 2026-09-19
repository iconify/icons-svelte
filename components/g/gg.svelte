<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czww5qr0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":34,"height":24};
const content = `<path class="czww5qr0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:gg" {...props}></Icon>
