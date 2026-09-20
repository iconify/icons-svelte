<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s26z6pb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s26z6pb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-badge-up" {...props}></Icon>
