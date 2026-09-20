<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6auz0bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6auz0bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:progress-4-fill" {...props}></Icon>
