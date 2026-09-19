<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg575skup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg575skup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:assistive-listening-device" {...props}></Icon>
