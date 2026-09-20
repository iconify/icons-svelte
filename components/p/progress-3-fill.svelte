<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcz2uwtww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcz2uwtww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:progress-3-fill" {...props}></Icon>
