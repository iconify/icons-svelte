<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5x5_rb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5x5_rb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:phone-end" {...props}></Icon>
