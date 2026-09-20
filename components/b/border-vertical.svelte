<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haz8x-boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haz8x-boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:border-vertical" {...props}></Icon>
