<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9gh00b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9gh00b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-check-corner-fill-round" {...props}></Icon>
