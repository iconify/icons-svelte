<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7o7g3z9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7o7g3z9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:memories-fill" {...props}></Icon>
