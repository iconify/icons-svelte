<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1uau39kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1uau39kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:key" {...props}></Icon>
