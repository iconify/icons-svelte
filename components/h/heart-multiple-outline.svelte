<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krhed0bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krhed0bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-multiple-outline" {...props}></Icon>
