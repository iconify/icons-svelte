<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn2s-smaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn2s-smaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-diagonal-s-line" {...props}></Icon>
