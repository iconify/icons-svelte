<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj9q3ubwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sj9q3ubwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:chevrons-right" {...props}></Icon>
