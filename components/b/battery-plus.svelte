<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2wc9qr1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2wc9qr1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:battery-plus" {...props}></Icon>
