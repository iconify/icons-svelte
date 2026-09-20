<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntog37p6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntog37p6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:document" {...props}></Icon>
