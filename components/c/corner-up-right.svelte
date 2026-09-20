<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl-eebb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl-eebb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:corner-up-right" {...props}></Icon>
