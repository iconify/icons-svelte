<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k02sjbb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k02sjbb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-right" {...props}></Icon>
