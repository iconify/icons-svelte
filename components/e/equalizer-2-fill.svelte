<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5vq2cbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5vq2cbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:equalizer-2-fill" {...props}></Icon>
