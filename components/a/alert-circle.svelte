<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fshn_2bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fshn_2bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alert-circle" {...props}></Icon>
