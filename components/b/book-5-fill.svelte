<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6dtqwb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6dtqwb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-5-fill" {...props}></Icon>
