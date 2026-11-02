<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unquf7bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unquf7bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-image-fill" {...props}></Icon>
