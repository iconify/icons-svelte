<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq8u3fbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="vq8u3fbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:edit" {...props}></Icon>
