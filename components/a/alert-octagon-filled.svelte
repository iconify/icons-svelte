<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai99w2ekb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai99w2ekb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alert-octagon-filled" {...props}></Icon>
