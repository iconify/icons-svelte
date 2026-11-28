<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwezv1bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwezv1bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gate-buffer-tri-state-solid" {...props}></Icon>
