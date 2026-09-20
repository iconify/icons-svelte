<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e77d1dtiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e77d1dtiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:controller-circle-right" {...props}></Icon>
