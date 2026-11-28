<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i748oxbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i748oxbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pull-request-clock" {...props}></Icon>
