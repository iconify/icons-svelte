<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2082-6zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2082-6zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:beaker-question" {...props}></Icon>
