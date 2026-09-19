<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0v6tp52x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0v6tp52x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-badge" {...props}></Icon>
