<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilwcwmynq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilwcwmynq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chess-king-solid" {...props}></Icon>
