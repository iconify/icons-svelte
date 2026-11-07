<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s47kc73dd.css';
import '../../css/q/q2tc4sbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s47kc73dd"/><path class="q2tc4sbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevron-last-bold" {...props}></Icon>
