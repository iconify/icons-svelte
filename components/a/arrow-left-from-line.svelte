<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilma5fblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilma5fblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-left-from-line" {...props}></Icon>
