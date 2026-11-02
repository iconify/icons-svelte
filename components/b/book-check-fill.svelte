<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejmxj6bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejmxj6bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-check-fill" {...props}></Icon>
