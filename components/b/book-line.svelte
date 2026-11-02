<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiazq6bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kiazq6bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-line" {...props}></Icon>
