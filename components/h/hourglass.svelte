<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teihqdf3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="teihqdf3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:hourglass" {...props}></Icon>
