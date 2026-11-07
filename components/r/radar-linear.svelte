<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftquq3bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftquq3bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radar-linear" {...props}></Icon>
