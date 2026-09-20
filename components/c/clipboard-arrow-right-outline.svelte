<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3x3cqb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3x3cqb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-arrow-right-outline" {...props}></Icon>
